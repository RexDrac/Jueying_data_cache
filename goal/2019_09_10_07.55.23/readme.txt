max-step-num: 2500000000
critic-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
critic-lr: 0.0003
max-path-num: 20
dsr-gait-freq: 1.667
loss-output-diff-coeff: 0
state-dim: 25
replay-buffer-size: 1000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-entropy-coeff: 0.0
train-step-num: 1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
HLC-frequency: 25
squash-action: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
total-step-num: 2500000000
gamma: 0.955
epoch-num: 500
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
joint-interpolation: True
Physics-frequency: 1000
LLC-frequency: 500
record-start-size: 10000.0
replay-start-size: 10000
imitation-weight: 0.5
render-eval: False
max-test-time: 10
actor-weight-decay: 1e-06
env-id: HumanoidBalanceFilter-v0
critic-l2-reg: 0.0003
bullet-default-PD: False
epoch-step-num: 5000000
loss-output-smooth-coeff: 1.0
gating-layer-size: [32, 32]
actor-l2-reg: 0.0003
batch-size: 128
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-dim: 12
expert-index: None
loss-output-bound-coeff: 0.0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-lr: 0.0003
tau: 0.001
gating-activation-fn: ['relu', 'relu', 'None']
task-weight: 0.5
max-train-time: 10
filter-torque: False
filter-action: True
replay-ratio: 1
rollout-step-num: 1
dsr-gait-period: 0.6
max-episode-num: 5000000
critic-layer-size: [256, 256]
gating-index: None
expert-num: 4
prioritized-exp-replay: True
critic-weight-decay: 1e-06
interpolation: False
actor-layer-size: [256, 256]
n-step: 1
max-path-step: 5000
actor-activation-fn: ['relu', 'relu', 'None']
test-num: 4
