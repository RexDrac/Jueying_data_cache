normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-layer-size: [256, 256]
gamma: 0.955
epoch-num: 500
state-dim: 25
bullet-default-PD: False
actor-l2-reg: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
train-step-num: 1
expert-index: None
joint-interpolation: True
expert-num: 4
interpolation: False
replay-buffer-size: 1000000
actor-lr: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-train-time: 10
tau: 0.001
max-path-step: 5000
LLC-frequency: 500
batch-size: 128
epoch-step-num: 5000000
squash-action: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
total-step-num: 2500000000
max-test-time: 10
loss-output-smooth-coeff: 1.0
max-step-num: 2500000000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
critic-lr: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
n-step: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-l2-reg: 0.0003
rollout-step-num: 1
actor-weight-decay: 1e-06
filter-action: True
gating-layer-size: [32, 32]
render-eval: False
gating-index: None
loss-entropy-coeff: 0.0
imitation-weight: 0.5
loss-output-diff-coeff: 0
gating-activation-fn: ['relu', 'relu', 'None']
action-dim: 12
env-id: HumanoidBalanceFilter-v0
reward-scale: 0.1
critic-activation-fn: ['relu', 'relu', 'None']
record-start-size: 10000.0
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
test-num: 4
dsr-gait-period: 0.6
replay-ratio: 1
filter-torque: False
dsr-gait-freq: 1.667
actor-activation-fn: ['relu', 'relu', 'None']
replay-start-size: 10000
max-path-num: 20
loss-output-bound-coeff: 0.0
Physics-frequency: 1000
HLC-frequency: 25
actor-layer-size: [256, 256]
prioritized-exp-replay: True
task-weight: 0.5
critic-weight-decay: 1e-06
max-episode-num: 5000000
