bullet-default-PD: False
batch-size: 128
loss-output-diff-coeff: 0
max-path-num: 20
loss-output-smooth-coeff: 2.0
rollout-step-num: 1
critic-activation-fn: ['relu', 'relu', 'None']
critic-weight-decay: 1e-06
state-dim: 23
train-step-num: 1
task-weight: 0.5
critic-lr: 0.0003
loss-output-bound-coeff: 0.0
max-test-time: 10
replay-buffer-size: 1000000
prioritized-exp-replay: True
filter-action: True
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
Physics-frequency: 1000
gating-activation-fn: ['relu', 'relu', 'None']
gating-layer-size: [32, 32]
imitation-weight: 0.5
actor-lr: 0.0003
render-eval: False
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
dsr-gait-period: 0.6
max-train-time: 10
expert-num: 4
actor-layer-size: [256, 256]
actor-l2-reg: 0.0003
expert-index: None
actor-activation-fn: ['relu', 'relu', 'None']
gamma: 0.955
epoch-num: 500
action-dim: 12
total-step-num: 2500000000
epoch-step-num: 5000000
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
critic-layer-size: [256, 256]
squash-action: True
actor-weight-decay: 1e-06
env-id: HumanoidBalanceFilter-v0
test-num: 4
LLC-frequency: 500
tau: 0.001
max-episode-num: 5000000
loss-entropy-coeff: 0.0
max-path-step: 5000
gating-index: None
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
joint-interpolation: True
n-step: 1
replay-ratio: 1
record-start-size: 10000.0
critic-l2-reg: 0.0003
HLC-frequency: 25
dsr-gait-freq: 1.667
replay-start-size: 10000
max-step-num: 2500000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
reward-scale: 0.1
filter-torque: False
interpolation: False
